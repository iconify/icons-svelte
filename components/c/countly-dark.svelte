<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h2cwtf82h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="h2cwtf82h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:countly-dark" {...props}></Icon>
