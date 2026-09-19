<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufeehvblu.css';
import '../../css/s/slb9bgbjc.css';
import '../../css/d/d3vk4h6tm.css';
import '../../css/n/nk3yzmb_b.css';
import '../../css/h/h12ov-btj.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGiclGCbnp"><g class="ufeehvblu"><path class="slb9bgbjc"/><path class="d3vk4h6tm"/><path class="nk3yzmb_b"/><path class="h12ov-btj"/></g></mask></defs><path mask="url(#SVGiclGCbnp)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:game-handle" {...props}></Icon>
