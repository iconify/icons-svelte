<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eauh11j5q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eauh11j5q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:bnb-line" {...props}></Icon>
