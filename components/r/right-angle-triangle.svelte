<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xg4taue4l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xg4taue4l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:right-angle-triangle" {...props}></Icon>
