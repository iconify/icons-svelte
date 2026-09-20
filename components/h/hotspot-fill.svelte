<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i7e5a7pja.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i7e5a7pja"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:hotspot-fill" {...props}></Icon>
