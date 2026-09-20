<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xvi7wnmts.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xvi7wnmts"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:layout-top-2-line" {...props}></Icon>
