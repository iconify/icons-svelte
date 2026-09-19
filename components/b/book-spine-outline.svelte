<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vh_t7actz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="vh_t7actz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:book-spine-outline" {...props}></Icon>
