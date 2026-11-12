<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z7ckltoed.css';
import '../../css/q/qmqaxfynj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="z7ckltoed"/><path class="qmqaxfynj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:koel-light" {...props}></Icon>
