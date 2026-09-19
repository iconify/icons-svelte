<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/o/or3aysb-z.css';
import '../../css/r/rdyict78a.css';
import '../../css/u/ua4-rlagr.css';
import '../../css/c/ct-v8-bvm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="or3aysb-z"/><path class="rdyict78a"/><path class="ua4-rlagr"/><path class="ct-v8-bvm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:images-1-outline" {...props}></Icon>
