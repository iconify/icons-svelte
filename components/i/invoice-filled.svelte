<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/co3u6ra6q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="co3u6ra6q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:invoice-filled" {...props}></Icon>
