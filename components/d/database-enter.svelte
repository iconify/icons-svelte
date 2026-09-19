<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nz_20wbpz.css';
import '../../css/j/jo1zsubfb.css';
import '../../css/l/lcee_744z.css';
import '../../css/r/rp6e00bkn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><path class="jo1zsubfb"/><path class="lcee_744z"/><path class="rp6e00bkn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:database-enter" {...props}></Icon>
