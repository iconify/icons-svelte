<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z8tbmnbml.css';
import '../../css/k/kpb0wubyn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="z8tbmnbml"/><path class="kpb0wubyn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:caddy" {...props}></Icon>
