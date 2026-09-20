<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hl6t_4w4h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hl6t_4w4h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:openhab-dark" {...props}></Icon>
