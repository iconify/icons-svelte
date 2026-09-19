<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sp1oxqb9n.css';
import '../../css/r/rr6qynbft.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="sp1oxqb9n"/><path class="rr6qynbft"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:airplay" {...props}></Icon>
