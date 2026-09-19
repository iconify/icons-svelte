<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nz_20wbpz.css';
import '../../css/s/s5kcr4b5f.css';
import '../../css/v/vu69zob8w.css';
import '../../css/u/ul-9w7bgg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><path class="s5kcr4b5f"/><path class="vu69zob8w"/><path class="ul-9w7bgg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:mac-finder" {...props}></Icon>
