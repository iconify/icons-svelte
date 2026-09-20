<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u4p2bsbtc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="u4p2bsbtc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:opnsense-v1-light" {...props}></Icon>
