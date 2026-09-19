<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vdkervi1l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vdkervi1l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:aero-bike" {...props}></Icon>
