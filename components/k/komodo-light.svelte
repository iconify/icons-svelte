<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qn412pbzn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qn412pbzn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:komodo-light" {...props}></Icon>
