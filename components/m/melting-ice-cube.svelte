<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/orf3lfbmm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="orf3lfbmm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:melting-ice-cube" {...props}></Icon>
