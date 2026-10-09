<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ih_a-vb3d.css';
import '../../css/t/tf0qaik3p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ih_a-vb3d"/><path class="tf0qaik3p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:cpu-20-bold" {...props}></Icon>
