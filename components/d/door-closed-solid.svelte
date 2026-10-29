<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x5e3orbgn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x5e3orbgn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:door-closed-solid" {...props}></Icon>
