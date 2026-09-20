<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k3re52bcw.css';
import '../../css/x/xqjtzac8e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="k3re52bcw"/><path class="xqjtzac8e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:mend-sast" {...props}></Icon>
