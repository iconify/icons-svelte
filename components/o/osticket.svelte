<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u4f5m8bpi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="u4f5m8bpi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:osticket" {...props}></Icon>
