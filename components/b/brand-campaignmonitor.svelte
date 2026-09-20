<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sbnbl3m4q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sbnbl3m4q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:brand-campaignmonitor" {...props}></Icon>
