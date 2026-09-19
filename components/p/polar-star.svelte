<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c2x-0cbks.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="c2x-0cbks"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:polar-star" {...props}></Icon>
