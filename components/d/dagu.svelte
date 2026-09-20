<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/va_1o5bbc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="va_1o5bbc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:dagu" {...props}></Icon>
