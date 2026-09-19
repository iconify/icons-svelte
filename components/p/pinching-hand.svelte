<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ojihu_awq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ojihu_awq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:pinching-hand" {...props}></Icon>
