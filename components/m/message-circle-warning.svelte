<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vy0alfbzj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vy0alfbzj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:message-circle-warning" {...props}></Icon>
