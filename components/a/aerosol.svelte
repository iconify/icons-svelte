<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s5jm6ac4h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s5jm6ac4h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:aerosol" {...props}></Icon>
