<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e0yfdjz0b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":432,"height":384};
const content = `<path class="e0yfdjz0b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:flickr" {...props}></Icon>
