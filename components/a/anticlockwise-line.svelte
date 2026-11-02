<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r05__4bvj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r05__4bvj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:anticlockwise-line" {...props}></Icon>
