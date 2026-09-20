<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ks8q3gsxp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ks8q3gsxp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:komodo-dark" {...props}></Icon>
