<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t7pgh2bpn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="t7pgh2bpn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:defguard" {...props}></Icon>
