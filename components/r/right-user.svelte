<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nz_20wbpz.css';
import '../../css/b/b6mu38bbk.css';
import '../../css/z/z6d_ftb-e.css';
import '../../css/r/rrf8tebmg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><circle class="b6mu38bbk"/><path class="z6d_ftb-e"/><path class="rrf8tebmg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:right-user" {...props}></Icon>
