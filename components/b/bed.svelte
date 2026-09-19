<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ru-y72bip.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ru-y72bip"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:bed" {...props}></Icon>
