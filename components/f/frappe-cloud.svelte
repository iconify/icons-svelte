<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d4_kwrboz.css';
import '../../css/a/az5k_yb4r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="d4_kwrboz"/><path class="az5k_yb4r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:frappe-cloud" {...props}></Icon>
