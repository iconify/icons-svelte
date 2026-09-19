<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/frlfe4b7z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="frlfe4b7z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:cigarette" {...props}></Icon>
