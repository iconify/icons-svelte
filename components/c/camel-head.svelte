<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cwrlgdc4r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="cwrlgdc4r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:camel-head" {...props}></Icon>
