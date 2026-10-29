<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/w/whk4pe4jr.css';
import '../../css/w/w4f1phn-n.css';
import '../../css/z/zegtxvsso.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="whk4pe4jr"/><path class="w4f1phn-n wm-a"/><path class="zegtxvsso"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:burger" {...props}></Icon>
