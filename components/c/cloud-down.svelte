<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j5-1zsbga.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="j5-1zsbga"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:cloud-down" {...props}></Icon>
