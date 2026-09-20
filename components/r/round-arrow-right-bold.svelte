<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c0p2vxb_k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="c0p2vxb_k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:round-arrow-right-bold" {...props}></Icon>
