<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a8z9hyvrf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="a8z9hyvrf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-brands:bluesky" {...props}></Icon>
