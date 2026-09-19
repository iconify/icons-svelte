<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pkevdq1tb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="pkevdq1tb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:bomb" {...props}></Icon>
