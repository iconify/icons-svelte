<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/drhte3_lk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="drhte3_lk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:interface-help-customer-support-4-customer-headset-help-phone-support" {...props}></Icon>
