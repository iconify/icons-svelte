<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m8ngi2bsq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="m8ngi2bsq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:nginx-proxy-manager-dark" {...props}></Icon>
