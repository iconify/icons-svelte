<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vid58lbtx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vid58lbtx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:dice-3" {...props}></Icon>
