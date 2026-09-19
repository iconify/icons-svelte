<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qkh_5cccx.css';
import '../../css/y/y9notdn4r.css';
import '../../css/m/m2o3sh-9c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":36,"height":36};
const content = `<path class="clr-i-outline--alerted clr-i-outline-path-1--alerted qkh_5cccx"/><path class="clr-i-alert clr-i-outline--alerted clr-i-outline-path-2--alerted y9notdn4r"/><path class="m2o3sh-9c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="clarity:block-outline-alerted" {...props}></Icon>
