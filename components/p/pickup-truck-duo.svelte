<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/c/csptg4b9v.css';
import '../../css/h/heeygwb2h.css';
import '../../css/l/l9ophzv3f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="csptg4b9v"/><path class="heeygwb2h"/><path class="l9ophzv3f"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:pickup-truck-duo" {...props}></Icon>
