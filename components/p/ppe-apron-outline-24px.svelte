<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ycg1ycc8m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ycg1ycc8m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:ppe-apron-outline-24px" {...props}></Icon>
