<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/j/j7cqu14cb.css';
import '../../css/o/o5q8363wp.css';
import '../../css/v/v90nhibmu.css';
import '../../css/v/vr41qqvca.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="j7cqu14cb"/><path class="o5q8363wp"/><path class="v90nhibmu"/><path class="vr41qqvca"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:caret-square-duo" {...props}></Icon>
