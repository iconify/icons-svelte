<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wjco2obit.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wjco2obit"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:pause-circle" {...props}></Icon>
