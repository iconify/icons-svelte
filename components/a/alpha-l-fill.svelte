<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dds2i6bod.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="dds2i6bod"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:alpha-l-fill" {...props}></Icon>
