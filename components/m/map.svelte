<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b4iliac4k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="b4iliac4k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:map" {...props}></Icon>
