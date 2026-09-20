<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hp49s6dbf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hp49s6dbf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:oil-temperature" {...props}></Icon>
