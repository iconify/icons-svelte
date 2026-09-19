<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cbu41_9ah.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="cbu41_9ah"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-regular:gem" {...props}></Icon>
