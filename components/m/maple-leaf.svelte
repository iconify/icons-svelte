<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rw419bc7v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="rw419bc7v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:maple-leaf" {...props}></Icon>
