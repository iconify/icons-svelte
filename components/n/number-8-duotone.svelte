<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/x/xow-v8lod.css';
import '../../css/k/k_uimnb6o.css';
import '../../css/h/hta0mxbau.css';
import '../../css/h/hhgyo3bul.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="xow-v8lod"/><circle class="k_uimnb6o"/><circle class="hta0mxbau"/><circle class="hhgyo3bul"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:number-8-duotone" {...props}></Icon>
