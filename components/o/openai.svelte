<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bov0584ws.css';
import '../../css/u/u6f-okb0z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bov0584ws"/><path class="u6f-okb0z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:openai" {...props}></Icon>
