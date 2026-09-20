<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k3re52bcw.css';
import '../../css/x/xl643povl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="k3re52bcw"/><path class="xl643povl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:mend-container" {...props}></Icon>
