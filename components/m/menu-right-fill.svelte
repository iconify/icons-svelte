<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j5sm3i20k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="j5sm3i20k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:menu-right-fill" {...props}></Icon>
