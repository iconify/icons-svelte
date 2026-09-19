<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sxz7cltnn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="sxz7cltnn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:bowl-with-spoon" {...props}></Icon>
