<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dutm75gbs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dutm75gbs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:piston" {...props}></Icon>
