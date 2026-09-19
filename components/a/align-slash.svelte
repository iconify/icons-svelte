<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bje2-jnxu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="bje2-jnxu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:align-slash" {...props}></Icon>
