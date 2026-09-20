<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pu21kfa1i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="pu21kfa1i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:rocky-linux-dark" {...props}></Icon>
