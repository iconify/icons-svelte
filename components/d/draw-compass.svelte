<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xnwr_1bhy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xnwr_1bhy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:draw-compass" {...props}></Icon>
