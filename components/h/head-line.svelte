<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/catzxre6a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="catzxre6a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:head-line" {...props}></Icon>
