<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xu7pm9p-z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xu7pm9p-z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:nginx-proxy-manager" {...props}></Icon>
