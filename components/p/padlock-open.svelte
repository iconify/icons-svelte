<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipss57bdc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ipss57bdc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:padlock-open" {...props}></Icon>
