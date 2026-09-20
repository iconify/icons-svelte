<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m4s_z9l1l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m4s_z9l1l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:map-pin-4-line" {...props}></Icon>
