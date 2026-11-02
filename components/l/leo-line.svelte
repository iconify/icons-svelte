<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zxx4xsbrj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zxx4xsbrj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:leo-line" {...props}></Icon>
