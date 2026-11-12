<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j8zjdfbvx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="j8zjdfbvx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:freeresend-light" {...props}></Icon>
