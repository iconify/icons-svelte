<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/obybe6j6t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="obybe6j6t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:anatomical-heart" {...props}></Icon>
