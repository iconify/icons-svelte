<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wbtrp5bnn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wbtrp5bnn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:chart-pie-alt" {...props}></Icon>
