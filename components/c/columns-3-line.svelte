<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pnpfy9s3u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pnpfy9s3u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:columns-3-line" {...props}></Icon>
