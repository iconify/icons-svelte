<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pd-4zjz7r.css';
import '../../css/o/ohm6g2bps.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="pd-4zjz7r"/><circle class="ohm6g2bps"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:planet-outline" {...props}></Icon>
