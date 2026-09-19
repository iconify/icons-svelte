<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lc96r_bum.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="lc96r_bum"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:discussion" {...props}></Icon>
