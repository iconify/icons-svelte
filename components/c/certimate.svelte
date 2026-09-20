<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r7jn51b8w.css';
import '../../css/v/vrnfpbw3e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<circle class="r7jn51b8w"/><path class="vrnfpbw3e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:certimate" {...props}></Icon>
