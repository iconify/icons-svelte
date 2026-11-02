<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vewl1d49k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vewl1d49k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:compass-fill" {...props}></Icon>
