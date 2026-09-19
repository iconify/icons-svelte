<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uok-79bon.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="uok-79bon"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:atomic-slashes" {...props}></Icon>
