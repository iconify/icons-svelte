<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pf_12gmma.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="pf_12gmma"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:headband-knot" {...props}></Icon>
