<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/li-6-8xig.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="li-6-8xig"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:backward" {...props}></Icon>
