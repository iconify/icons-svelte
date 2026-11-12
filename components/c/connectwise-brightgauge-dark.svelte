<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rq76f0bli.css';
import '../../css/k/kjglpe2ae.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rq76f0bli"/><path class="kjglpe2ae"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:connectwise-brightgauge-dark" {...props}></Icon>
