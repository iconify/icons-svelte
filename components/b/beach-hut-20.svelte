<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n83w2qbdq.css';
import '../../css/u/um-eanbbz.css';
import '../../css/k/k3w3y09sg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="n83w2qbdq"/><path class="um-eanbbz"/><path class="k3w3y09sg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:beach-hut-20" {...props}></Icon>
