<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/j/j7cqu14cb.css';
import '../../css/h/h2eecabmn.css';
import '../../css/v/v90nhibmu.css';
import '../../css/h/hg98oub6d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="j7cqu14cb"/><path class="h2eecabmn"/><path class="v90nhibmu"/><path class="hg98oub6d"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:arrow-solid-square-duo" {...props}></Icon>
