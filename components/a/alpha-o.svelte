<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sqau-cbvt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="sqau-cbvt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:alpha-o" {...props}></Icon>
