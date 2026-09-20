<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dce6tfrbb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="dce6tfrbb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:peertube-light" {...props}></Icon>
