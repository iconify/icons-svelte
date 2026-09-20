<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s5f9-ubrk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s5f9-ubrk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:camera-metering-matrix" {...props}></Icon>
