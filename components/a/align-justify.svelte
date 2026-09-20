<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oi1t57hvf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oi1t57hvf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:align-justify" {...props}></Icon>
