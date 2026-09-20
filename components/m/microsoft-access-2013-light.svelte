<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nxlw5-52r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="nxlw5-52r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:microsoft-access-2013-light" {...props}></Icon>
