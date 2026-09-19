<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vz3g6ebxf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vz3g6ebxf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:internal-injury" {...props}></Icon>
