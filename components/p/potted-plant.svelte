<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c32_iib3k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path clip-rule="evenodd" class="c32_iib3k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:potted-plant" {...props}></Icon>
