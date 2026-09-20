<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hh6h6accl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hh6h6accl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:cursor-off" {...props}></Icon>
