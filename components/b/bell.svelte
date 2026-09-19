<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j3h-9fb2n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="j3h-9fb2n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:bell" {...props}></Icon>
