<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/va_mebb_q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":1025};
const content = `<path class="va_mebb_q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:metro" {...props}></Icon>
