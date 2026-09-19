<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/su4ixfbhf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="su4ixfbhf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bx-loader-alt" {...props}></Icon>
