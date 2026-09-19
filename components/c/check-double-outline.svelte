<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/t/thzgjtb1r.css';
import '../../css/x/x7s3ef7xj.css';
import '../../css/f/f2_p00lwq.css';
import '../../css/d/d67rd9bsz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="thzgjtb1r"/><path class="x7s3ef7xj"/><path class="f2_p00lwq"/><path class="d67rd9bsz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:check-double-outline" {...props}></Icon>
