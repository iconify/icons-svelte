<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mhhps6bkj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mhhps6bkj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:chart-no-axes-combined" {...props}></Icon>
