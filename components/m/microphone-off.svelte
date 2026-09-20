<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/t/tvn6ntdsb.css';
import '../../css/y/ybzbxbbqr.css';
import '../../css/g/gd5-rmb8p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="tvn6ntdsb"/><path class="ybzbxbbqr"/><path class="gd5-rmb8p"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="proicons:microphone-off" {...props}></Icon>
