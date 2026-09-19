<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/q/qls5yob2g.css';
import '../../css/q/qlh9ednwc.css';
import '../../css/u/u3-h_p5za.css';
import '../../css/b/bsgsx4b-b.css';
import '../../css/p/p_03qcbda.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="qls5yob2g"/><path class="qlh9ednwc"/><path class="u3-h_p5za"/><path class="bsgsx4b-b"/><path class="p_03qcbda"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-flat:eleven-thirty" {...props}></Icon>
