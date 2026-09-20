<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oxrsvbbge.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="oxrsvbbge"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:alpine-linux-dark" {...props}></Icon>
