<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cevh89b7w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="cevh89b7w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:capricorn" {...props}></Icon>
