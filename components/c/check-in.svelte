<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nz_20wbpz.css';
import '../../css/m/mkd5n7taf.css';
import '../../css/y/y_e_yzf5i.css';
import '../../css/u/u4-tff-3z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><path class="mkd5n7taf"/><path class="y_e_yzf5i"/><path class="u4-tff-3z"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:check-in" {...props}></Icon>
