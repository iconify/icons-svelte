<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e8t8phb8t.css';
import '../../css/k/k9nd7m2gk.css';
import '../../css/o/ol1wuwbkq.css';
import '../../css/c/ce-taw9ke.css';
import '../../css/l/l_iwwg5oc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="e8t8phb8t"/><path class="k9nd7m2gk"/><path class="ol1wuwbkq"/><path class="ce-taw9ke"/><path class="l_iwwg5oc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-flash-off" {...props}></Icon>
