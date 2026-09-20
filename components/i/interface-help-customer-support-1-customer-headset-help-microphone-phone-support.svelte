<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sjm12_boi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="sjm12_boi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:interface-help-customer-support-1-customer-headset-help-microphone-phone-support" {...props}></Icon>
