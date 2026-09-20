<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qdt9a3kty.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="qdt9a3kty"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:milk-carton-and-apple-and-yen-yuan" {...props}></Icon>
