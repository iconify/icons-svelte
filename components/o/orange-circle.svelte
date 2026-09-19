<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tqt407r5l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="tqt407r5l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:orange-circle" {...props}></Icon>
