<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p51s5nbfp.css';
import '../../css/v/vdipyz_so.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="p51s5nbfp"/><path class="vdipyz_so"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:google-analytics" {...props}></Icon>
