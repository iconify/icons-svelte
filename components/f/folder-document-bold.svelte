<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r3kb4cgpl.css';
import '../../css/d/dnynulurz.css';
import '../../css/d/d3c1e1uyw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="r3kb4cgpl"><path class="dnynulurz"/><path class="d3c1e1uyw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:folder-document-bold" {...props}></Icon>
