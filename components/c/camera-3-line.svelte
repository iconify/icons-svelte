<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w-rtdmbnk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w-rtdmbnk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:camera-3-line" {...props}></Icon>
