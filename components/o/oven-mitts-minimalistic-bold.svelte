<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cfknu2blj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cfknu2blj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:oven-mitts-minimalistic-bold" {...props}></Icon>
