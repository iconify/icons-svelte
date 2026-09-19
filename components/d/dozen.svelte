<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y99voxbqk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="y99voxbqk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:dozen" {...props}></Icon>
