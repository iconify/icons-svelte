<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z4d115tme.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="z4d115tme"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:eyes" {...props}></Icon>
