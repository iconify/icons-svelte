<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pcsx5kbyb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="pcsx5kbyb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:falling-blob" {...props}></Icon>
