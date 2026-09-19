<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yf8n3pwcf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="yf8n3pwcf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:akka" {...props}></Icon>
