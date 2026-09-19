<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xn0-01bqi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="xn0-01bqi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:closed-umbrella" {...props}></Icon>
