<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/va4l_-boi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="va4l_-boi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:abstract-051" {...props}></Icon>
