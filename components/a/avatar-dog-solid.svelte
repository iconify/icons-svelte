<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lwtr5_pps.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lwtr5_pps"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:avatar-dog-solid" {...props}></Icon>
