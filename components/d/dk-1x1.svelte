<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e7fr20m4o.css';
import '../../css/g/g6shwtddl.css';
import '../../css/q/q8u0wn3hp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="e7fr20m4o"/><path class="g6shwtddl"/><path class="q8u0wn3hp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flag:dk-1x1" {...props}></Icon>
