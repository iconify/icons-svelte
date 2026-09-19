<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wp84hibku.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="wp84hibku"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:diamond-suit" {...props}></Icon>
