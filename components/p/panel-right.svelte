<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xk6pe--vp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xk6pe--vp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:panel-right" {...props}></Icon>
