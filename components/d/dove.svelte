<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lsojb92fe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="lsojb92fe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:dove" {...props}></Icon>
