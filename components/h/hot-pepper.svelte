<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fota-cc9k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="fota-cc9k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:hot-pepper" {...props}></Icon>
