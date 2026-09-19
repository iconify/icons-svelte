<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l2iu8cnhj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="l2iu8cnhj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:headset" {...props}></Icon>
