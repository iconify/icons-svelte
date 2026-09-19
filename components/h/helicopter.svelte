<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1lsf0bnc.css';
import '../../css/u/u4vxdxfpw.css';
import '../../css/o/oog0pjbel.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":16};
const content = `<g class="n1lsf0bnc"><path class="u4vxdxfpw"/><path class="oog0pjbel"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:helicopter" {...props}></Icon>
