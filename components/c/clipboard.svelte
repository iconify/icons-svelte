<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l0ds9_bxf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="l0ds9_bxf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:clipboard" {...props}></Icon>
