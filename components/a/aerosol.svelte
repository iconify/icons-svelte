<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/plxs-nt5e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="plxs-nt5e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:aerosol" {...props}></Icon>
