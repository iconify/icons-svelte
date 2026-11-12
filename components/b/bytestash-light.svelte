<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ub19e0-yg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ub19e0-yg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:bytestash-light" {...props}></Icon>
