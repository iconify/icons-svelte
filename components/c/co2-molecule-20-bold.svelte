<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d-pu_abiq.css';
import '../../css/m/m2fwg6b2k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="d-pu_abiq"/><path class="m2fwg6b2k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:co2-molecule-20-bold" {...props}></Icon>
