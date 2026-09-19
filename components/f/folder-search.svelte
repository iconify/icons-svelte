<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1lsf0bnc.css';
import '../../css/l/lhqj5vb6u.css';
import '../../css/p/pfijgcd8z.css';
import '../../css/i/imeoqsh9e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<g class="n1lsf0bnc"><path class="lhqj5vb6u"/><path class="pfijgcd8z"/><path class="imeoqsh9e"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:folder-search" {...props}></Icon>
