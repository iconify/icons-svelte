<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/taqcn9bfg.css';
import '../../css/b/bbny_5ghg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="taqcn9bfg"/><path class="bbny_5ghg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:eonvelope-dark" {...props}></Icon>
