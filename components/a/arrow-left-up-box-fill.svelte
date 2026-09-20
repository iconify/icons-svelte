<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d_hndv8xy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d_hndv8xy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:arrow-left-up-box-fill" {...props}></Icon>
