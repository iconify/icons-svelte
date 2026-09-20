<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i8c4q0b7c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i8c4q0b7c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:hazard-lights" {...props}></Icon>
