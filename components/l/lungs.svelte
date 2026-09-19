<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yxbwxls6p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="yxbwxls6p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:lungs" {...props}></Icon>
