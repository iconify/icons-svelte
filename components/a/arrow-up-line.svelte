<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ynf_x9b6q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ynf_x9b6q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:arrow-up-line" {...props}></Icon>
