<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/n/ntho9dxzt.css';
import '../../css/l/l08oyi90u.css';
import '../../css/a/ac6xbtk3v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="ntho9dxzt"/><path class="l08oyi90u"/><path class="ac6xbtk3v"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:printer" {...props}></Icon>
