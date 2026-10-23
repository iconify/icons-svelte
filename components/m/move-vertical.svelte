<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a85bfdc6l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a85bfdc6l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:move-vertical" {...props}></Icon>
