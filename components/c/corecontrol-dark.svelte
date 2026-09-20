<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kz5t110yc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="kz5t110yc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:corecontrol-dark" {...props}></Icon>
