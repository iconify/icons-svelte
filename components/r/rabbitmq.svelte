<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wnwp0xbgh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wnwp0xbgh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:rabbitmq" {...props}></Icon>
