<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w0tdrhhdk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="w0tdrhhdk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:alpha-x" {...props}></Icon>
