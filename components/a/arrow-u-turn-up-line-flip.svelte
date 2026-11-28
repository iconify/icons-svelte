<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/t/t1ydkablc.css';
import '../../css/r/r5r6k0bua.css';
import '../../css/p/pbgkwbc_y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="t1ydkablc"/><path class="r5r6k0bua"/><path class="pbgkwbc_y"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:arrow-u-turn-up-line-flip" {...props}></Icon>
