<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c7k6u3b2p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="c7k6u3b2p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:card-random" {...props}></Icon>
