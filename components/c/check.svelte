<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/a/a7l40-h5j.css';
import '../../css/e/e_g3rh9bx.css';
import '../../css/q/qs7l13kmi.css';
import '../../css/m/mn0wur4ce.css';
import '../../css/h/hkaf77b0d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="a7l40-h5j wm-k"/><path class="e_g3rh9bx wm-k"/><path class="qs7l13kmi wm-k"/><path class="mn0wur4ce wm-shine"/><path class="hkaf77b0d wm-deco"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-anime:check" {...props}></Icon>
