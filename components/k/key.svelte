<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/y/yg19ojb2y.css';
import '../../css/u/udesl-8lq.css';
import '../../css/k/kccmp_b5b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="yg19ojb2y"/><path class="udesl-8lq"/><path class="kccmp_b5b"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:key" {...props}></Icon>
