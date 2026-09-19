<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nz_20wbpz.css';
import '../../css/x/xl-dk0l-y.css';
import '../../css/t/tm9f74uep.css';
import '../../css/i/igbkoxb2y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><path class="xl-dk0l-y"/><circle class="tm9f74uep"/><path class="igbkoxb2y"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:flip-camera" {...props}></Icon>
