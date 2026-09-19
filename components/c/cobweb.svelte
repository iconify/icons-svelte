<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ntbt6bcny.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ntbt6bcny"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:cobweb" {...props}></Icon>
