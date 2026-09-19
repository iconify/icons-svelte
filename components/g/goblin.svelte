<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/osyj73brr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="osyj73brr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:goblin" {...props}></Icon>
