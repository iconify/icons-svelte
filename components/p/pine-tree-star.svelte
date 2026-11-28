<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m45mxib6s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m45mxib6s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:pine-tree-star" {...props}></Icon>
