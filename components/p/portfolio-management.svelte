<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fwlbj0b8j.css';
import '../../css/q/q1p1kwjdw.css';
import '../../css/m/m1y4hsbgq.css';
import '../../css/v/vh1dgbcue.css';
import '../../css/t/tzrsdpb2g.css';
import '../../css/m/mxv0-rl9y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="fwlbj0b8j"/><path class="q1p1kwjdw"/><circle class="m1y4hsbgq"/><circle class="vh1dgbcue"/><path class="tzrsdpb2g"/><path class="mxv0-rl9y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:portfolio-management" {...props}></Icon>
