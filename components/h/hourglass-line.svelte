<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zl2xvtbdq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zl2xvtbdq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:hourglass-line" {...props}></Icon>
