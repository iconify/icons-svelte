<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z_9aq5btt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="z_9aq5btt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:heart-outline" {...props}></Icon>
