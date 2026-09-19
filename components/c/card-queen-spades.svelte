<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/akcv2kb9u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="akcv2kb9u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:card-queen-spades" {...props}></Icon>
