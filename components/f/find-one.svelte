<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nz_20wbpz.css';
import '../../css/x/x4kvhkb3w.css';
import '../../css/b/bhpciutjo.css';
import '../../css/l/lczvgixin.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><path class="x4kvhkb3w"/><path class="bhpciutjo"/><path class="lczvgixin"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:find-one" {...props}></Icon>
