<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ii5c8ebjh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ii5c8ebjh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:angler-fish" {...props}></Icon>
