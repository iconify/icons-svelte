<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/za7uqbcjq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="za7uqbcjq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:dvd" {...props}></Icon>
