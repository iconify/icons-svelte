<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sn39y8buz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="sn39y8buz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:countly-light" {...props}></Icon>
