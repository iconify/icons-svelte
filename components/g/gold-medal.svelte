<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nz_20wbpz.css';
import '../../css/m/m66g3kb5k.css';
import '../../css/g/g00mx43ai.css';
import '../../css/i/ij785dbcr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><path class="m66g3kb5k"/><path class="g00mx43ai"/><path class="ij785dbcr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:gold-medal" {...props}></Icon>
