<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e-5vqbbjg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="e-5vqbbjg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:cactus" {...props}></Icon>
