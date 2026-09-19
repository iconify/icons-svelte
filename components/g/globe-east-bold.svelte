<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/b/bpin_ybto.css';
import '../../css/c/csq7p7s1r.css';
import '../../css/v/v09bwgbwj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="bpin_ybto"/><path clip-rule="evenodd" class="csq7p7s1r"/><path class="v09bwgbwj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:globe-east-bold" {...props}></Icon>
