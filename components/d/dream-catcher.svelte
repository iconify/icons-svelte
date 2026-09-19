<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ie3otbb4o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ie3otbb4o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:dream-catcher" {...props}></Icon>
