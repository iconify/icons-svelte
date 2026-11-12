<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ev6_nwamt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ev6_nwamt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:authgear-light" {...props}></Icon>
