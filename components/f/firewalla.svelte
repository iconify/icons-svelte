<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zjs8erx3y.css';
import '../../css/c/cwxu7xb2c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zjs8erx3y"/><path class="cwxu7xb2c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:firewalla" {...props}></Icon>
