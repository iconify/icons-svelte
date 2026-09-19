<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nczn-tzkd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nczn-tzkd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:filter-solid" {...props}></Icon>
