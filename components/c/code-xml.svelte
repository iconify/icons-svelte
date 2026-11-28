<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/m/mzhlhi47b.css';
import '../../css/m/m8cg0rb7a.css';
import '../../css/s/sbba9kb4d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="mzhlhi47b"/><path class="m8cg0rb7a"/><path class="sbba9kb4d"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:code-xml" {...props}></Icon>
