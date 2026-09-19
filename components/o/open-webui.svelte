<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x-n25z4ll.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x-n25z4ll"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:open-webui" {...props}></Icon>
