<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eu6db3bkt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="eu6db3bkt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:bucket" {...props}></Icon>
