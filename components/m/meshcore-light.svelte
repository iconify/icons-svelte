<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h227az4ss.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="h227az4ss"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:meshcore-light" {...props}></Icon>
