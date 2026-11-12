<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x3xehe9tz.css';
import '../../css/k/koobuxbzj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="x3xehe9tz"/><path class="koobuxbzj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:feeds-fun-light" {...props}></Icon>
