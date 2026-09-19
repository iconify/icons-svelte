<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kx131-biu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kx131-biu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-alarm-off" {...props}></Icon>
