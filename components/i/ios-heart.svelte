<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a2515opfd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="a2515opfd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-heart" {...props}></Icon>
