<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vxwa7ub6s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="vxwa7ub6s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:bold-g" {...props}></Icon>
