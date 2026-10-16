<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/icyfw2p5c.css';
import '../../css/g/g2jzfhoqs.css';
import '../../css/r/rjsh6cbuu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="icyfw2p5c"/><path class="g2jzfhoqs"/><path class="rjsh6cbuu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:cherry-picker-48-bold" {...props}></Icon>
