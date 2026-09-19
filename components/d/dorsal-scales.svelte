<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vyilz1b9d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vyilz1b9d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:dorsal-scales" {...props}></Icon>
