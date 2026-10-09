<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cfdfq4bue.css';
import '../../css/i/iaalw5bbu.css';
import '../../css/t/t8dqc66mp.css';
import '../../css/v/vqbc74-cp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="cfdfq4bue"/><path class="iaalw5bbu"/><path class="t8dqc66mp"/><path class="vqbc74-cp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:electric-car-x-48" {...props}></Icon>
