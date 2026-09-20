<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o8kplqktf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o8kplqktf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:mobile-signal-two-solid" {...props}></Icon>
