<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z8tbmnbml.css';
import '../../css/k/k-c9kibht.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="z8tbmnbml"/><path class="k-c9kibht"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:caddy" {...props}></Icon>
