<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/grtguubyu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="grtguubyu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="subway:fullscreen" {...props}></Icon>
