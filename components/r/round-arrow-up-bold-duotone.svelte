<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xrdvcwidb.css';
import '../../css/w/wyg5aebcj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xrdvcwidb"/><path class="wyg5aebcj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:round-arrow-up-bold-duotone" {...props}></Icon>
