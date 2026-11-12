<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ixo81-b_z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ixo81-b_z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:planarally-light" {...props}></Icon>
