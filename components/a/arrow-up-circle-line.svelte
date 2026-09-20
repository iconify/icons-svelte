<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cl8ymybgs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cl8ymybgs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:arrow-up-circle-line" {...props}></Icon>
