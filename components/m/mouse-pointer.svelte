<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m5e-wnbhe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m5e-wnbhe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:mouse-pointer" {...props}></Icon>
