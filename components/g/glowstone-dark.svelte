<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dooibm0ta.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="dooibm0ta"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:glowstone-dark" {...props}></Icon>
