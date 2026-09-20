<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s5rq7pvid.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="s5rq7pvid"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:mediux-dark" {...props}></Icon>
