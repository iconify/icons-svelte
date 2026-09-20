<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qrde4zxpv.css';
import '../../css/m/m-85-0blw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="qrde4zxpv"/><path class="m-85-0blw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:bakery-15" {...props}></Icon>
