<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qv_hzn8gl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qv_hzn8gl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:iframe" {...props}></Icon>
