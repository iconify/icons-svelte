<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h006f82xz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="h006f82xz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:faved-light" {...props}></Icon>
