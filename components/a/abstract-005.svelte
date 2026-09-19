<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ifu3skbry.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ifu3skbry"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:abstract-005" {...props}></Icon>
