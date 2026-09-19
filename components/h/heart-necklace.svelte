<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ezga8i1ck.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ezga8i1ck"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:heart-necklace" {...props}></Icon>
