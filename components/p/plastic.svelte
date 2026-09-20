<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e9fy4pb2e.css';
import '../../css/d/dgefbvkwi.css';
import '../../css/h/hyxzxriuy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<g class="e9fy4pb2e"><path class="dgefbvkwi"/><path class="hyxzxriuy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:plastic" {...props}></Icon>
