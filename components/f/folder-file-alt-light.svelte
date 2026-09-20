<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h01tyzbfu.css';
import '../../css/x/xrfgp0bpp.css';
import '../../css/v/vc02c23rw.css';
import '../../css/x/xtch0nbcn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="h01tyzbfu"><path class="xrfgp0bpp"/><path class="vc02c23rw"/><path class="xtch0nbcn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:folder-file-alt-light" {...props}></Icon>
