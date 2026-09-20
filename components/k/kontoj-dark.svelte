<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a5c65ns3i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="a5c65ns3i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:kontoj-dark" {...props}></Icon>
