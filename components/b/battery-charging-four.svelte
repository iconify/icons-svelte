<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/ti1ys_bcu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ti1ys_bcu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:battery-charging-four" {...props}></Icon>
