<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d_2x2fbfq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="d_2x2fbfq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:purple-square" {...props}></Icon>
