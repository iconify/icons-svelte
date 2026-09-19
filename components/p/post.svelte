<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p2u9y6bny.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":1024};
const content = `<path class="p2u9y6bny"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:post" {...props}></Icon>
