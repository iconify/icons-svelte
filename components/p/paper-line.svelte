<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pcjnfmbuf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pcjnfmbuf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:paper-line" {...props}></Icon>
