<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xk3va7a2y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xk3va7a2y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-folder-minus" {...props}></Icon>
