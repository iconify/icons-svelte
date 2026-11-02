<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k6-c51b7q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k6-c51b7q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:pencil-2-fill" {...props}></Icon>
