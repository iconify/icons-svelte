<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ejrj45bop.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ejrj45bop"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:hockey-20-bold" {...props}></Icon>
