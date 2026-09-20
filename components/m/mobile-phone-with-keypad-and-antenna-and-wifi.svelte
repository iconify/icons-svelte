<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iy-cs117v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="iy-cs117v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:mobile-phone-with-keypad-and-antenna-and-wifi" {...props}></Icon>
