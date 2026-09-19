<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nz_20wbpz.css';
import '../../css/c/cwxxxccvd.css';
import '../../css/m/mz6gfbc4a.css';
import '../../css/g/g0etr6b-w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><path class="cwxxxccvd"/><rect class="mz6gfbc4a"/><path class="g0etr6b-w"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:barber-clippers" {...props}></Icon>
