<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nz_20wbpz.css';
import '../../css/l/lcee_744z.css';
import '../../css/e/ezjk6mb0l.css';
import '../../css/j/jo1zsubfb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><path class="lcee_744z"/><path class="ezjk6mb0l"/><path class="jo1zsubfb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:database-position" {...props}></Icon>
