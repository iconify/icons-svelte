<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xng5u_b3c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xng5u_b3c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:pen-draw" {...props}></Icon>
