<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x3hp9nbvt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x3hp9nbvt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:oven-solid" {...props}></Icon>
