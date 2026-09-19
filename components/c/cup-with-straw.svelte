<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qdap3vb6e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="qdap3vb6e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:cup-with-straw" {...props}></Icon>
