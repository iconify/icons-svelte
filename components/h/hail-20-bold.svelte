<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dx_6a7bpx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="dx_6a7bpx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:hail-20-bold" {...props}></Icon>
