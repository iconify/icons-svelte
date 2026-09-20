<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f96sd9b1j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f96sd9b1j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:gamepad-up" {...props}></Icon>
