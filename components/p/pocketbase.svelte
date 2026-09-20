<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sqs373j8m.css';
import '../../css/l/l_lpikbgk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="sqs373j8m"/><path class="l_lpikbgk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:pocketbase" {...props}></Icon>
