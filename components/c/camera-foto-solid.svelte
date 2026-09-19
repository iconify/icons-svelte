<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/ph-l3p-7w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ph-l3p-7w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:camera-foto-solid" {...props}></Icon>
