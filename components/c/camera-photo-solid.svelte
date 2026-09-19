<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipzj944da.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ipzj944da"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:camera-photo-solid" {...props}></Icon>
