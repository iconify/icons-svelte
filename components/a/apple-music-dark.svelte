<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j5i7l73zx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="j5i7l73zx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:apple-music-dark" {...props}></Icon>
