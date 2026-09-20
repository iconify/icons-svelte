<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/co3ape_oq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="co3ape_oq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:portainer-v1" {...props}></Icon>
