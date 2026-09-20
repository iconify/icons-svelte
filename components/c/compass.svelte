<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tc-vztb9o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tc-vztb9o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:compass" {...props}></Icon>
