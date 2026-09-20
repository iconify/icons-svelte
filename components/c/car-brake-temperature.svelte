<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h40y5cb7r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h40y5cb7r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:car-brake-temperature" {...props}></Icon>
