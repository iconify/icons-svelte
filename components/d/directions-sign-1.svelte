<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x-s8crb-y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="x-s8crb-y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:directions-sign-1" {...props}></Icon>
