<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nz_20wbpz.css';
import '../../css/l/l356zpi2t.css';
import '../../css/p/p-ijq8p6w.css';
import '../../css/p/pvs97mopz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":49,"height":48};
const content = `<g class="nz_20wbpz"><path class="l356zpi2t"/><circle class="p-ijq8p6w"/><path class="pvs97mopz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:dashboard-one" {...props}></Icon>
