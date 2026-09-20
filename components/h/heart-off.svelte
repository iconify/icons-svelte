<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b_yz9qbsv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b_yz9qbsv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:heart-off" {...props}></Icon>
