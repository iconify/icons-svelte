<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nv9qcacyl.css';
import '../../css/k/krvb6vbdu.css';
import '../../css/d/d79ru3bml.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<g class="nv9qcacyl"><path class="krvb6vbdu"/><path class="d79ru3bml"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flag:mc-1x1" {...props}></Icon>
