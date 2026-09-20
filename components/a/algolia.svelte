<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/g/g58yorbkc.css';
import '../../css/m/mvgayujde.css';
import '../../css/m/mdlzjj5jz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":485,"height":120};
const content = `<g class="ft5dv1b6b"><path class="g58yorbkc"/><path class="mvgayujde"/><path class="mdlzjj5jz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:algolia" {...props}></Icon>
