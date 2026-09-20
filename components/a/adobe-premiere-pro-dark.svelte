<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v1sv1_bsq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="v1sv1_bsq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:adobe-premiere-pro-dark" {...props}></Icon>
