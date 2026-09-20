<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zytt76bsb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zytt76bsb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:map-pin-line" {...props}></Icon>
