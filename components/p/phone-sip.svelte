<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hy3b7ss8t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":384};
const content = `<path class="hy3b7ss8t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:phone-sip" {...props}></Icon>
