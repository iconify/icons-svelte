<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kpay2-_kv.css';
import '../../css/n/nix21vnhc.css';
import '../../css/m/m2o3sh-9c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":36,"height":36};
const content = `<path class="clr-i-outline clr-i-outline-path-1 kpay2-_kv"/><path class="clr-i-outline clr-i-outline-path-2 nix21vnhc"/><path class="m2o3sh-9c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="clarity:resize-down-line" {...props}></Icon>
