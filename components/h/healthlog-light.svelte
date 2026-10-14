<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x0tvb20ai.css';
import '../../css/r/r1hiqbchs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="x0tvb20ai"/><path class="r1hiqbchs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:healthlog-light" {...props}></Icon>
