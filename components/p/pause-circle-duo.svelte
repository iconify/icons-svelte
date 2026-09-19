<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/l/lafhkbbho.css';
import '../../css/v/v45bkcq0b.css';
import '../../css/w/w4vxnac6h.css';
import '../../css/d/d4yadoppj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="lafhkbbho"/><path class="v45bkcq0b"/><path class="w4vxnac6h"/><path class="d4yadoppj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:pause-circle-duo" {...props}></Icon>
