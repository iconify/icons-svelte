<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/icyvf5brz.css';
import '../../css/b/bfueulvzi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="icyvf5brz"/><path class="bfueulvzi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:post-content" {...props}></Icon>
