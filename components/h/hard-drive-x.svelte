<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cyy11la5q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cyy11la5q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:hard-drive-x" {...props}></Icon>
