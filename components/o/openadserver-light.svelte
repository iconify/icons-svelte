<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r_9rqpxcs.css';
import '../../css/z/zc6vvbcxg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="r_9rqpxcs"/><path class="zc6vvbcxg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:openadserver-light" {...props}></Icon>
