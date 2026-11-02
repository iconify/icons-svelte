<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bfk2hn2kh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bfk2hn2kh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:bridge-2-fill" {...props}></Icon>
