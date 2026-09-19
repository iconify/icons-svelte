<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ibpb4ib8a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ibpb4ib8a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:palette" {...props}></Icon>
