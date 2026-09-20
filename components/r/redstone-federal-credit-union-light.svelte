<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r5t0um5rr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="r5t0um5rr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:redstone-federal-credit-union-light" {...props}></Icon>
