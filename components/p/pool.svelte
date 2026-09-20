<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vcet0h_kb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vcet0h_kb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:pool" {...props}></Icon>
