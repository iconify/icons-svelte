<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w3qc8vbdk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="w3qc8vbdk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:computer-battery-empty-1-phone-mobile-charge-device-electricity-empty-power-battery" {...props}></Icon>
