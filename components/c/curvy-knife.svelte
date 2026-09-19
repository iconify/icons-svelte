<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nbe650b-l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="nbe650b-l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:curvy-knife" {...props}></Icon>
