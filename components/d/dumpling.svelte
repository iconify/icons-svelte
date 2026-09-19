<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vs1j0v5_d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vs1j0v5_d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:dumpling" {...props}></Icon>
