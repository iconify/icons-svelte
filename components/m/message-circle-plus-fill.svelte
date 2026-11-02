<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x-t1h_slz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x-t1h_slz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:message-circle-plus-fill" {...props}></Icon>
