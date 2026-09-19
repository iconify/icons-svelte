<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o9aa4ibqx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="o9aa4ibqx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:ring-buoy" {...props}></Icon>
