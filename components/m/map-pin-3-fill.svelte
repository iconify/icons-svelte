<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ygif3dzbs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ygif3dzbs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:map-pin-3-fill" {...props}></Icon>
