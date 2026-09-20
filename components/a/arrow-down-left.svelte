<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cee9hacjd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="cee9hacjd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:arrow-down-left" {...props}></Icon>
