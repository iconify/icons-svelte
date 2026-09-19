<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s4wl_ub8n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="s4wl_ub8n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:bottle-cap" {...props}></Icon>
