<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/riad1mbxn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="riad1mbxn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:chart-pie" {...props}></Icon>
