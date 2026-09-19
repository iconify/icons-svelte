<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m5vy0x2pp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="m5vy0x2pp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:musical-score" {...props}></Icon>
