<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p45bg4ozx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="p45bg4ozx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:openleaf-light" {...props}></Icon>
