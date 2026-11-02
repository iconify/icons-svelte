<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ybq5mxb3x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ybq5mxb3x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:numbers-90-sort-ascending-fill" {...props}></Icon>
