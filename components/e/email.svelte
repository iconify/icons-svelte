<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bvwm3wm-l.css';
import '../../css/z/zgyoyfbth.css';
import '../../css/v/vsqobsshi.css';
import '../../css/x/xagkgcbsq.css';
import '../../css/j/jfn9918qi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bvwm3wm-l"/><path class="zgyoyfbth"/><path class="vsqobsshi"/><path class="xagkgcbsq"/><path class="jfn9918qi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:email" {...props}></Icon>
