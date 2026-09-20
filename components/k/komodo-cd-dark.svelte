<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cx-f89bpi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="cx-f89bpi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:komodo-cd-dark" {...props}></Icon>
