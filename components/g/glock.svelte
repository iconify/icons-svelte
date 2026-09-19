<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mmbr0-b_b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mmbr0-b_b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:glock" {...props}></Icon>
