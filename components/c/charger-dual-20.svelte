<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pv4p-irnn.css';
import '../../css/m/moo4i7zmp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="pv4p-irnn"/><path class="moo4i7zmp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:charger-dual-20" {...props}></Icon>
