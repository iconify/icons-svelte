<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ad97a97cl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ad97a97cl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:grip-vertical" {...props}></Icon>
