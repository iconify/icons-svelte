<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/m/m6triwbzc.css';
import '../../css/w/w4f1phn-n.css';
import '../../css/j/jf-6btauh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="m6triwbzc"/><path class="w4f1phn-n wm-a"/><path class="jf-6btauh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:burger-duo" {...props}></Icon>
