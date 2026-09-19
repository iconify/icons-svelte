<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/r/rvubgbbtn.css';
import '../../css/u/u-dp037qb.css';
import '../../css/c/cii--0b6u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="rvubgbbtn"/><path clip-rule="evenodd" class="u-dp037qb"/><path class="cii--0b6u"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons:music-note-double-print" {...props}></Icon>
