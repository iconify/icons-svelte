<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kso4zxb6q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kso4zxb6q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:add-square-fill" {...props}></Icon>
