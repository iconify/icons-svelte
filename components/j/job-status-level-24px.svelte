<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/td1t-5bcx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="td1t-5bcx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:job-status-level-24px" {...props}></Icon>
