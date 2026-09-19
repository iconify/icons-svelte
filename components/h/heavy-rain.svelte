<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vf8oocclb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vf8oocclb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:heavy-rain" {...props}></Icon>
