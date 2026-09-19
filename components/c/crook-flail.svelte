<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l0dxcsb9s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="l0dxcsb9s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:crook-flail" {...props}></Icon>
