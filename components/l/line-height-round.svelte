<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jz8d_fbfl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jz8d_fbfl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:line-height-round" {...props}></Icon>
