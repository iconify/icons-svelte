<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p7jvj_bep.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="p7jvj_bep"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:mobile-phone-with-keypad-and-antenna-and-bolt" {...props}></Icon>
