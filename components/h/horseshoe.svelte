<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tf3q7_mjn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tf3q7_mjn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:horseshoe" {...props}></Icon>
