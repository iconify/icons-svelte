<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/y/ycmz1urwb.css';
import '../../css/o/oi9gvkbqh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":300,"height":216};
const content = `<g class="ft5dv1b6b"><path class="ycmz1urwb"/><path class="oi9gvkbqh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cif:al" {...props}></Icon>
