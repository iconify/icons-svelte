<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iav3n6ptp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iav3n6ptp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:order-ascending" {...props}></Icon>
