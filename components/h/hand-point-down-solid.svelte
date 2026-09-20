<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w0e06xb_t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="w0e06xb_t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:hand-point-down-solid" {...props}></Icon>
