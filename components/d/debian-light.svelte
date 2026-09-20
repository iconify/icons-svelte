<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y9tw6t4sl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="y9tw6t4sl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:debian-light" {...props}></Icon>
