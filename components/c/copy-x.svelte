<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/i/ib4ikg6hx.css';
import '../../css/e/ekk1d4bph.css';
import '../../css/i/ixff_67er.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="ib4ikg6hx"/><path class="ekk1d4bph"/><path class="ixff_67er"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:copy-x" {...props}></Icon>
