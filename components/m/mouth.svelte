<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yfsc4vbkf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="yfsc4vbkf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:mouth" {...props}></Icon>
