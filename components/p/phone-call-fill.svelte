<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/td9l-etip.css';
import '../../css/x/xatcsgbad.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="td9l-etip"/><path class="xatcsgbad"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:phone-call-fill" {...props}></Icon>
