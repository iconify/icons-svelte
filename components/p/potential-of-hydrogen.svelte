<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k_vp0ma3m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k_vp0ma3m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:potential-of-hydrogen" {...props}></Icon>
