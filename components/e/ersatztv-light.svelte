<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iddnc4agt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="iddnc4agt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:ersatztv-light" {...props}></Icon>
