<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fa584bojz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="fa584bojz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:lizard-tongue" {...props}></Icon>
