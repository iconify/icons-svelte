<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipte8ubfi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ipte8ubfi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:progress-4-line" {...props}></Icon>
