<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cb_ragf0m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cb_ragf0m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:arm-outline-24px" {...props}></Icon>
