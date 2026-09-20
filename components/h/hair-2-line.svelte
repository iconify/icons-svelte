<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vxf-x0wmr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vxf-x0wmr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:hair-2-line" {...props}></Icon>
