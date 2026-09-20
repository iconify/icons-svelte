<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/slc1jnbcy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="slc1jnbcy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:lyft-light" {...props}></Icon>
