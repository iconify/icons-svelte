<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nxz7st9fi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nxz7st9fi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:candy-cane-outline" {...props}></Icon>
