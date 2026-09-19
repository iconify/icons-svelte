<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nz_20wbpz.css';
import '../../css/o/oxacldbke.css';
import '../../css/d/dsln90bva.css';
import '../../css/v/vm5l4wnay.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><path class="oxacldbke"/><path class="dsln90bva"/><circle class="vm5l4wnay"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:folder-music-one" {...props}></Icon>
