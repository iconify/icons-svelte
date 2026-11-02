<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xjgk6__av.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xjgk6__av"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:delete-line" {...props}></Icon>
