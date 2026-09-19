<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ox6fy5dxe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ox6fy5dxe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-home-smile" {...props}></Icon>
