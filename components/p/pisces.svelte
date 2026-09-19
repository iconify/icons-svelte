<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g6nrprqvg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="g6nrprqvg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:pisces" {...props}></Icon>
