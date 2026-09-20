<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l-zmqpb1k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="l-zmqpb1k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:calibre-web-dark" {...props}></Icon>
