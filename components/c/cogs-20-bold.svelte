<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xg8tnbcvl.css';
import '../../css/s/sx-04bc4i.css';
import '../../css/r/rwowwm9cp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="xg8tnbcvl"/><path class="sx-04bc4i"/><path class="rwowwm9cp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:cogs-20-bold" {...props}></Icon>
