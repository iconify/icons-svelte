<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i6pswusna.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="i6pswusna"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:abstract-081" {...props}></Icon>
