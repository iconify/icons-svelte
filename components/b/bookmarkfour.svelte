<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d1da3i3qu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":1025};
const content = `<path class="d1da3i3qu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:bookmarkfour" {...props}></Icon>
