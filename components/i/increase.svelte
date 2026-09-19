<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nz_20wbpz.css';
import '../../css/p/p2qes6yjx.css';
import '../../css/z/zwzneibzu.css';
import '../../css/c/c85xlhb2g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><path class="p2qes6yjx"/><path class="zwzneibzu"/><path class="c85xlhb2g"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:increase" {...props}></Icon>
