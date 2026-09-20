<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yr04_fblc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yr04_fblc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:horizontal-rotate-counterclockwise" {...props}></Icon>
