<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b6e8x6blc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="b6e8x6blc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:ice-hockey" {...props}></Icon>
