<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iix0k_bgr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="iix0k_bgr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:checkmark-rectangle-fill" {...props}></Icon>
