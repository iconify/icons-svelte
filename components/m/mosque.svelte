<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zohv35dbe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="zohv35dbe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:mosque" {...props}></Icon>
