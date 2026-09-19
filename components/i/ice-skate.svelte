<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ncxchm-0b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ncxchm-0b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:ice-skate" {...props}></Icon>
