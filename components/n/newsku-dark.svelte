<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ywsqo5b5s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ywsqo5b5s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:newsku-dark" {...props}></Icon>
