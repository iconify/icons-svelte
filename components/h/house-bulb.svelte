<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j-83rxbaj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j-83rxbaj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:house-bulb" {...props}></Icon>
