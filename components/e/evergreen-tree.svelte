<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hysehgb4l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="hysehgb4l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:evergreen-tree" {...props}></Icon>
