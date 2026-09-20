<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dvu2p6bej.css';
import '../../css/s/ss065ksnd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="dvu2p6bej"/><path class="ss065ksnd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:perfice-light" {...props}></Icon>
