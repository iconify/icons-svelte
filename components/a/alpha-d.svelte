<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ogr483q8j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="ogr483q8j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:alpha-d" {...props}></Icon>
