<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vm3ivccum.css';
import '../../css/r/rd9mw5o4z.css';
import '../../css/f/fp94dub4c.css';
import '../../css/x/xq36oibuq.css';
import '../../css/i/i46u6tbey.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="vm3ivccum"><rect class="rd9mw5o4z"/><path class="fp94dub4c"/><circle class="xq36oibuq"/><path class="i46u6tbey"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:camera-three" {...props}></Icon>
