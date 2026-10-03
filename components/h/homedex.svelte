<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ew16t5bon.css';
import '../../css/m/mfhjfna5c.css';
import '../../css/b/b3g89hl7j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ew16t5bon"/><path class="mfhjfna5c"/><path class="b3g89hl7j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:homedex" {...props}></Icon>
