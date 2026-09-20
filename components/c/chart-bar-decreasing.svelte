<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wekaxpy_z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wekaxpy_z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:chart-bar-decreasing" {...props}></Icon>
