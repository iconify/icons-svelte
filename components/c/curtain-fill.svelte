<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t0yx-r6qe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t0yx-r6qe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:curtain-fill" {...props}></Icon>
