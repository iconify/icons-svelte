<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uatcl-bly.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="uatcl-bly"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="subway:round-arrow-6" {...props}></Icon>
