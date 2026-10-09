<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/onux0z-vm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="onux0z-vm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:cloud-20-bold" {...props}></Icon>
