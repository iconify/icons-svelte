<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zkpk_n84s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zkpk_n84s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:quetre" {...props}></Icon>
