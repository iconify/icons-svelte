<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/istg6zbfd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="istg6zbfd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:import-line" {...props}></Icon>
