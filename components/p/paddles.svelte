<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vmzzk0bns.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vmzzk0bns"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:paddles" {...props}></Icon>
