<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cmv_hrb-s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cmv_hrb-s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:robot-vacuum-alert" {...props}></Icon>
