<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/roj7v4bmf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="roj7v4bmf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand:connect-flash" {...props}></Icon>
