<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/y/y1q597bvf.css';
import '../../css/a/ad44mbiog.css';
import '../../css/l/loqsov77d.css';
import '../../css/l/lpmrlkbpq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="y1q597bvf"/><path class="ad44mbiog"/><path class="loqsov77d"/><path class="lpmrlkbpq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:key-outline" {...props}></Icon>
