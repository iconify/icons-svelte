<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rz2-0f1zi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rz2-0f1zi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fe:eraser" {...props}></Icon>
