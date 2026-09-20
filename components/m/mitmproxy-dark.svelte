<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h40arjbpi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="h40arjbpi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:mitmproxy-dark" {...props}></Icon>
