<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ne2d3dzjs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ne2d3dzjs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:phice-light" {...props}></Icon>
