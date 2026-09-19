<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/e/eon37-7oa.css';
import '../../css/y/y31nl7bsa.css';
import '../../css/h/hyc9jcbmb.css';
import '../../css/d/ducbzu09b.css';
import '../../css/h/hznjk-boo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="eon37-7oa"/><path class="y31nl7bsa"/><circle class="hyc9jcbmb"/><path class="ducbzu09b"/><path clip-rule="evenodd" class="hznjk-boo"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs-poly:kiss-wink-heart" {...props}></Icon>
