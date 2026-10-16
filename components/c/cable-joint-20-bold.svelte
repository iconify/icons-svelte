<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vwfgn5qgs.css';
import '../../css/q/qa0e82m0b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="vwfgn5qgs"/><path class="qa0e82m0b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:cable-joint-20-bold" {...props}></Icon>
