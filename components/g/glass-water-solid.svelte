<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vtu15_roz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vtu15_roz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:glass-water-solid" {...props}></Icon>
