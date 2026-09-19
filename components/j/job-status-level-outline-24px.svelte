<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vka6x62mp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vka6x62mp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:job-status-level-outline-24px" {...props}></Icon>
