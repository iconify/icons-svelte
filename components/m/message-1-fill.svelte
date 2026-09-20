<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y_3rjki6h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y_3rjki6h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:message-1-fill" {...props}></Icon>
