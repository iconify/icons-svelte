<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/inexm0bxc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="inexm0bxc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:edge-crack" {...props}></Icon>
