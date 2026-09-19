<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kaclnvm2k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="kaclnvm2k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:bell-pepper" {...props}></Icon>
