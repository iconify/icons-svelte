<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/spnx_mb2q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="spnx_mb2q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:bagpipes" {...props}></Icon>
