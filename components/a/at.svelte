<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q7ev_gi8u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="q7ev_gi8u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs-poly:at" {...props}></Icon>
