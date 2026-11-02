<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t7-5x6g7q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t7-5x6g7q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:heart-minus-fill" {...props}></Icon>
