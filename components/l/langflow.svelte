<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/shdyh8bir.css';
import '../../css/a/ay_63acmb.css';
import '../../css/d/dyv9fpbor.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="shdyh8bir"/><path class="ay_63acmb"/><path class="dyv9fpbor"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:langflow" {...props}></Icon>
