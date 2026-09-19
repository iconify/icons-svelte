<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w29npqbft.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="w29npqbft"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:cherry-blossom" {...props}></Icon>
