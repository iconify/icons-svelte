<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qhjc_3plp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qhjc_3plp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:actual-mcp-server-dark" {...props}></Icon>
