<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n4e15yayf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="n4e15yayf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:kiosk-device" {...props}></Icon>
