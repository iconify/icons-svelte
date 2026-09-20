<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k_46b9bjg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k_46b9bjg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:chart-bar-decreasing-solid" {...props}></Icon>
