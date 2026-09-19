<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bwoq-nw4g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="bwoq-nw4g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:aquarius" {...props}></Icon>
