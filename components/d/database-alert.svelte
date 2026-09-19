<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nz_20wbpz.css';
import '../../css/l/lcee_744z.css';
import '../../css/d/d0whacb4t.css';
import '../../css/k/kj14aabfk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><path class="lcee_744z"/><path class="d0whacb4t"/><path class="kj14aabfk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:database-alert" {...props}></Icon>
