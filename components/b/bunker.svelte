<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gv_4_mzrl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="gv_4_mzrl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:bunker" {...props}></Icon>
