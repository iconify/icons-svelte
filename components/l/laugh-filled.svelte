<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vxq9lab-m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vxq9lab-m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:laugh-filled" {...props}></Icon>
