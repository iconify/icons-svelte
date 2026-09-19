<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ubsgd0b7a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ubsgd0b7a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:hourglass-done" {...props}></Icon>
