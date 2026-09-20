<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cpprrl-oc.css';
import '../../css/j/jtvf014yy.css';
import '../../css/t/tuwlzzbuq.css';
import '../../css/b/brzn_0bpr.css';
import '../../css/a/anumt-d7o.css';
import '../../css/f/fh24wh2_x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="cpprrl-oc"/><path class="jtvf014yy"/><circle class="tuwlzzbuq"/><g class="brzn_0bpr"><circle class="anumt-d7o"/><path class="fh24wh2_x"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:hair-pick" {...props}></Icon>
