<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dcsnbtokg.css';
import '../../css/f/fffxy750p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<circle class="dcsnbtokg"/><path class="fffxy750p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:loops" {...props}></Icon>
