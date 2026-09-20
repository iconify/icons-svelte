<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ndndjv9pq.css';
import '../../css/q/qmqaxfynj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ndndjv9pq"/><path class="qmqaxfynj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:koel-light" {...props}></Icon>
