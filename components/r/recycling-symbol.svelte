<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r384vcbfe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="r384vcbfe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:recycling-symbol" {...props}></Icon>
