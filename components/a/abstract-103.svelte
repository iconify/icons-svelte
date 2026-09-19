<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ibdyugogr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ibdyugogr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:abstract-103" {...props}></Icon>
