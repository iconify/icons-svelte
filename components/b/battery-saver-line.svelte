<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t_u8-1key.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t_u8-1key"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:battery-saver-line" {...props}></Icon>
