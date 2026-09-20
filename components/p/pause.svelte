<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tzkfv2_pz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tzkfv2_pz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mi:pause" {...props}></Icon>
