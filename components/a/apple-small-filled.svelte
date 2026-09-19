<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x1do2fb_e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="x1do2fb_e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:apple-small-filled" {...props}></Icon>
