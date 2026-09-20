<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ri6lrnb_l.css';
import '../../css/i/ibxo5zbky.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="ri6lrnb_l"/><path class="ibxo5zbky"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:raised-hand-light-skin-tone" {...props}></Icon>
