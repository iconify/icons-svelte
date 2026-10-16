<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aivqjwruh.css';
import '../../css/o/oinxi2bcn.css';
import '../../css/k/kp65e56pe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="aivqjwruh"/><path class="oinxi2bcn"/><path class="kp65e56pe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:compost-48-bold" {...props}></Icon>
