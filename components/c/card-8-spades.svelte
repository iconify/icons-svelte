<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mky1-gb8j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mky1-gb8j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:card-8-spades" {...props}></Icon>
