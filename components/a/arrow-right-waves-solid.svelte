<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iadd8ybpx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iadd8ybpx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:arrow-right-waves-solid" {...props}></Icon>
