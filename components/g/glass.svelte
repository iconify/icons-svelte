<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s6dg5j3rg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":1023};
const content = `<path class="s6dg5j3rg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:glass" {...props}></Icon>
