<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pj0462s5o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="pj0462s5o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:raster" {...props}></Icon>
