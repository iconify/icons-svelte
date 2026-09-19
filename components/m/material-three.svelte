<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/t/ty8l4nl8s.css';
import '../../css/y/yi7ddnb4w.css';
import '../../css/p/pr05wzb5d.css';
import '../../css/t/thdjtvtxr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="ft5dv1b6b"><path class="ty8l4nl8s"/><path class="yi7ddnb4w"/><path clip-rule="evenodd" class="pr05wzb5d"/><path class="thdjtvtxr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:material-three" {...props}></Icon>
