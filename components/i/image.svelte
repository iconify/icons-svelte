<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ybl9i-bit.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="ybl9i-bit"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:image" {...props}></Icon>
