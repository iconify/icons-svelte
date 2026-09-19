<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tqydtnghr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="tqydtnghr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:nail-polish" {...props}></Icon>
