<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aonepje_a.css';
import '../../css/h/h0wavjb7c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="aonepje_a"/><path class="h0wavjb7c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:prosody" {...props}></Icon>
