<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fuus5rbmo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="fuus5rbmo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:full-screen-exit" {...props}></Icon>
