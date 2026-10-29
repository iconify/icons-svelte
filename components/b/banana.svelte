<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d2kvgvbvc.css';
import '../../css/i/is8p2nbel.css';
import '../../css/r/r35bzkbxd.css';
import '../../css/w/wl97hswxc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="d2kvgvbvc"><path class="is8p2nbel"/><path class="r35bzkbxd"/><path class="wl97hswxc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:banana" {...props}></Icon>
