<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r_9rqpxcs.css';
import '../../css/b/bm9ngmkam.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="r_9rqpxcs"/><path class="bm9ngmkam"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:openadserver-light" {...props}></Icon>
