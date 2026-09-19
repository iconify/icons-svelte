<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/q/qqfh5ojmb.css';
import '../../css/h/hsv1gfhcq.css';
import '../../css/z/z4cigfbsf.css';
import '../../css/x/xrnmq47gl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><circle class="qqfh5ojmb"/><circle class="hsv1gfhcq"/><circle class="z4cigfbsf"/><path class="xrnmq47gl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:music-album-duotone" {...props}></Icon>
