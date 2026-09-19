<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ik9sszbmp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ik9sszbmp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:poison" {...props}></Icon>
