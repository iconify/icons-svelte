<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ll7zn4iyj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ll7zn4iyj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:arrow-up-fill" {...props}></Icon>
