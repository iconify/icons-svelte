<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yc1d4tesh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="yc1d4tesh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:key" {...props}></Icon>
