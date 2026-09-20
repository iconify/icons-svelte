<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dzn6d_bpx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dzn6d_bpx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:parasol" {...props}></Icon>
