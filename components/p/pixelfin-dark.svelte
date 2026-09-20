<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sifyjwf_z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="sifyjwf_z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:pixelfin-dark" {...props}></Icon>
