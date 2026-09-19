<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iq13s2klb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="iq13s2klb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:ice-bolt" {...props}></Icon>
