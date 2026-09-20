<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xijeu059d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xijeu059d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:netboot-xyz-dark" {...props}></Icon>
