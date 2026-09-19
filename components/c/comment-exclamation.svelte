<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/f/fggntxbto.css';
import '../../css/p/pykr1s3ee.css';
import '../../css/e/eotwmrmzs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="fggntxbto"/><path class="pykr1s3ee"/><path class="eotwmrmzs"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs-poly:comment-exclamation" {...props}></Icon>
