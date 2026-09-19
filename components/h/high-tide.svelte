<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ieo3-je4y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ieo3-je4y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:high-tide" {...props}></Icon>
