<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vmlbdlbfq.css';
import '../../css/k/kvfqgdcvb.css';
import '../../css/l/lpwt15b-r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vmlbdlbfq"/><circle class="kvfqgdcvb"/><path class="lpwt15b-r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:person-add-sharp" {...props}></Icon>
