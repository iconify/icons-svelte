<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wxc2s3uyh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wxc2s3uyh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:jetkvm-light" {...props}></Icon>
