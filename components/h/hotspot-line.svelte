<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o_cnftb1z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o_cnftb1z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:hotspot-line" {...props}></Icon>
