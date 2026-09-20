<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mfoj36bvd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mfoj36bvd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:quickstack-light" {...props}></Icon>
