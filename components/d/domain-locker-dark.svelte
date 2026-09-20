<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l-eww7bvd.css';
import '../../css/y/y18qkbg3r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="l-eww7bvd"/><path class="y18qkbg3r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:domain-locker-dark" {...props}></Icon>
