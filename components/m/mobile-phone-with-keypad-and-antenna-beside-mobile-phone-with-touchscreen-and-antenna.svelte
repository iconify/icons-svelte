<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lsu17feyn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="lsu17feyn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:mobile-phone-with-keypad-and-antenna-beside-mobile-phone-with-touchscreen-and-antenna" {...props}></Icon>
