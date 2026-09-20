<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v-3ex_hwt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v-3ex_hwt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:device-ipad-horizontal-x" {...props}></Icon>
