<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gn0i6acvj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="gn0i6acvj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:overtchat-light" {...props}></Icon>
