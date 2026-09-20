<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/evtuy-b0v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="evtuy-b0v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:changedetection" {...props}></Icon>
