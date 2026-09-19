<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ycjz8iydj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ycjz8iydj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-copyright" {...props}></Icon>
