<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bm1ssabvx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bm1ssabvx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:portainer-v1-light" {...props}></Icon>
