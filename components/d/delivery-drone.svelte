<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ro3btb_ny.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ro3btb_ny"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:delivery-drone" {...props}></Icon>
