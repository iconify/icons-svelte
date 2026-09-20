<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oniymqrar.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oniymqrar"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand:network-laptop-1" {...props}></Icon>
