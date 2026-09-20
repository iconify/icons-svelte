<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ymgf6m1vx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ymgf6m1vx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:numbers-90-sort-ascending-fill" {...props}></Icon>
