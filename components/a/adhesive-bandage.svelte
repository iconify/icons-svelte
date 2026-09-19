<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vv17vp8ce.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="vv17vp8ce"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:adhesive-bandage" {...props}></Icon>
