<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zu-a57w1h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":11,"height":11};
const content = `<path class="zu-a57w1h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:landmark-jp-11" {...props}></Icon>
