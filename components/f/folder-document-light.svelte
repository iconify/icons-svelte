<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/ddvgu8bvv.css';
import '../../css/d/dnynulurz.css';
import '../../css/d/d3c1e1uyw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ddvgu8bvv"><path class="dnynulurz"/><path class="d3c1e1uyw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:folder-document-light" {...props}></Icon>
