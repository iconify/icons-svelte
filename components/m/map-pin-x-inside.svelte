<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o9a0_ey8u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o9a0_ey8u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:map-pin-x-inside" {...props}></Icon>
