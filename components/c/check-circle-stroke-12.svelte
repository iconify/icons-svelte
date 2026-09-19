<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h01tyzbfu.css';
import '../../css/d/d4l60oblr.css';
import '../../css/u/uf8-wnb5o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<g class="h01tyzbfu"><path class="d4l60oblr"/><circle class="uf8-wnb5o"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:check-circle-stroke-12" {...props}></Icon>
