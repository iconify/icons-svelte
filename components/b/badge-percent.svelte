<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/l/l4--ovbba.css';
import '../../css/l/l5j_-zs8c.css';
import '../../css/y/y78mtrb0d.css';
import '../../css/l/lb_vcvwoy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="l4--ovbba"/><path class="l5j_-zs8c"/><path class="y78mtrb0d"/><path class="lb_vcvwoy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:badge-percent" {...props}></Icon>
