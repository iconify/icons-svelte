<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uty38ab5q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uty38ab5q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:3d-move" {...props}></Icon>
