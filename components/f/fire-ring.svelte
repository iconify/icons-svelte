<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v4fb5ehck.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="v4fb5ehck"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:fire-ring" {...props}></Icon>
