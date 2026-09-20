<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z2yme1wsh.css';
import '../../css/w/wyg7xl8ps.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":11,"height":11};
const content = `<path class="z2yme1wsh"/><path class="wyg7xl8ps"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:college-11" {...props}></Icon>
