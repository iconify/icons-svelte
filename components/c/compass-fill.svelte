<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ohxr4pnsg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ohxr4pnsg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:compass-fill" {...props}></Icon>
