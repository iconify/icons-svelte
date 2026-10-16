<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m2ike7bth.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="m2ike7bth"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:crankshaft-48" {...props}></Icon>
