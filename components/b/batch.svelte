<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xp7upebym.css';
import '../../css/k/kvn-2v0wt.css';
import '../../css/e/e7s-dwrnc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<g class="xp7upebym"><path class="kvn-2v0wt"/><path class="e7s-dwrnc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="catppuccin:batch" {...props}></Icon>
