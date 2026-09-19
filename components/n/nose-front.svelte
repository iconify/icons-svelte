<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dvtifwbgw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="dvtifwbgw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:nose-front" {...props}></Icon>
