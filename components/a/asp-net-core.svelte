<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/or51mp33s.css';
import '../../css/l/ljtl2bbyd.css';
import '../../css/m/mhsun10on.css';
import '../../css/o/oai19b_2d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="or51mp33s"/><path class="ljtl2bbyd"/><path class="mhsun10on"/><path class="oai19b_2d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:asp-net-core" {...props}></Icon>
