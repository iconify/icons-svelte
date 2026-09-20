<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sm80p_y1i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="sm80p_y1i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:notification" {...props}></Icon>
