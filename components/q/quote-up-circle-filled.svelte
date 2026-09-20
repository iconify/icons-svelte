<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y-t85g_vj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y-t85g_vj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:quote-up-circle-filled" {...props}></Icon>
