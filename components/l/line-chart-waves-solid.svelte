<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bgnbkldne.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bgnbkldne"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:line-chart-waves-solid" {...props}></Icon>
