<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ry9s8zawo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ry9s8zawo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:eye-check" {...props}></Icon>
