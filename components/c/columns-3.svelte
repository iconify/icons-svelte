<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qyli_12yh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qyli_12yh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:columns-3" {...props}></Icon>
