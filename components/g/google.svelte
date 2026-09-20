<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/j/jwgpxoo3x.css';
import '../../css/t/tk71-d9_p.css';
import '../../css/d/dm3lzbbtn.css';
import '../../css/j/jvu_1rs4r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="jwgpxoo3x"/><path class="tk71-d9_p"/><path class="dm3lzbbtn"/><path class="jvu_1rs4r"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:google" {...props}></Icon>
