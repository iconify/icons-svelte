<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/r/rk2fecb1r.css';
import '../../css/v/vt8eloboj.css';
import '../../css/n/nsy6y-lmr.css';
import '../../css/l/lhfjjhbjh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="rk2fecb1r"/><path class="vt8eloboj"/><path class="nsy6y-lmr"/><path class="lhfjjhbjh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-flat:lime" {...props}></Icon>
