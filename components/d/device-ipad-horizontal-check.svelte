<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wk_up-b-r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wk_up-b-r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:device-ipad-horizontal-check" {...props}></Icon>
