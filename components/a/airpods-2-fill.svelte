<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s8iesjbwg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s8iesjbwg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:airpods-2-fill" {...props}></Icon>
