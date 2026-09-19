<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/otc8jfbmx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path clip-rule="evenodd" class="otc8jfbmx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:dog-face" {...props}></Icon>
