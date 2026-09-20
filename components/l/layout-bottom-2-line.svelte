<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/ssxhl_u_x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ssxhl_u_x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:layout-bottom-2-line" {...props}></Icon>
