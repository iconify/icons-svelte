<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eppxe-npy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eppxe-npy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:connectdevelop" {...props}></Icon>
