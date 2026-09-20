<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jiaf6kb4x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="jiaf6kb4x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:barrel-with-bunghole" {...props}></Icon>
