<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vycj0ibcd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vycj0ibcd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:folder-output-fill" {...props}></Icon>
