<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/y/yt58mxs7i.css';
import '../../css/t/tgz-nedht.css';
import '../../css/p/psfupr9nf.css';
import '../../css/r/rkfl4pgii.css';
import '../../css/f/fsxewn2rq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":30};
const content = `<g class="ft5dv1b6b"><path class="yt58mxs7i"/><path class="tgz-nedht"/><path class="psfupr9nf"/><path class="rkfl4pgii"/><path class="fsxewn2rq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:posthog" {...props}></Icon>
