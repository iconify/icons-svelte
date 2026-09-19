<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1lsf0bnc.css';
import '../../css/f/f_f3a9b3b.css';
import '../../css/w/w3d-tf10v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":16};
const content = `<g transform="translate(1 1)" class="n1lsf0bnc"><path class="f_f3a9b3b"/><circle class="w3d-tf10v"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:picture" {...props}></Icon>
