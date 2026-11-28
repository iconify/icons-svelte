<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/l/l4--ovbba.css';
import '../../css/e/eaazhxb8r.css';
import '../../css/t/t67ti6bya.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="l4--ovbba"/><path class="eaazhxb8r"/><path class="t67ti6bya"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:badge-cent" {...props}></Icon>
