<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zrv606btm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zrv606btm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:plane-takeoff-filled" {...props}></Icon>
