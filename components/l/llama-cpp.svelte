<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d5e2uw75d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="d5e2uw75d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:llama-cpp" {...props}></Icon>
