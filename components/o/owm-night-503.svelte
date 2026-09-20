<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i4t2ktbpz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":30};
const content = `<path class="i4t2ktbpz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wi:owm-night-503" {...props}></Icon>
