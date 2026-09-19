<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wpnd-hvwn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wpnd-hvwn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:chevron-down-outline" {...props}></Icon>
