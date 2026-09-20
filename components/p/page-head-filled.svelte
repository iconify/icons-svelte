<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ioer6yhnf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ioer6yhnf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:page-head-filled" {...props}></Icon>
