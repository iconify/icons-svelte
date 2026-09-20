<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/taqcn9bfg.css';
import '../../css/c/cijv3ebdv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="taqcn9bfg"/><path class="cijv3ebdv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:eonvelope-dark" {...props}></Icon>
