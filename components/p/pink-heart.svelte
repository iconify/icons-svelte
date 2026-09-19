<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w_trbkfzc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path clip-rule="evenodd" class="w_trbkfzc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:pink-heart" {...props}></Icon>
