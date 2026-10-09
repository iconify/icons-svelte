<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vqni3wbon.css';
import '../../css/v/vmxlixb3w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="vqni3wbon"/><path class="vmxlixb3w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:coffee-20" {...props}></Icon>
