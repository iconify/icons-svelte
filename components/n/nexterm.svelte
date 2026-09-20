<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zqmurns_d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zqmurns_d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:nexterm" {...props}></Icon>
