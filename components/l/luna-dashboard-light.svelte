<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m0hk8168n.css';
import '../../css/e/e5i_hobjt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="m0hk8168n"/><path class="e5i_hobjt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:luna-dashboard-light" {...props}></Icon>
