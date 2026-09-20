<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/l/l--oi22kl.css';
import '../../css/q/q7__kib4o.css';
import '../../css/x/x6y_sybsh.css';
import '../../css/q/qgfd6sb9e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="l--oi22kl"/><path class="q7__kib4o"/><path class="x6y_sybsh"/><path class="qgfd6sb9e"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:cpu" {...props}></Icon>
