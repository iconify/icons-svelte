<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p_yksccyr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="p_yksccyr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:music-spell" {...props}></Icon>
