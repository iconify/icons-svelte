<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gv7mcpbjq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="gv7mcpbjq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:myip" {...props}></Icon>
