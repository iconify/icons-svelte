<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bw9le9bcs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bw9le9bcs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:restore-line" {...props}></Icon>
