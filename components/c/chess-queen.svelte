<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ii217uehi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ii217uehi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:chess-queen" {...props}></Icon>
