<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ow64u_brv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ow64u_brv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:ceiling-fan" {...props}></Icon>
