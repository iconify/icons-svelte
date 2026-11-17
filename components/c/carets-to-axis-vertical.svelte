<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c0dfs_59j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c0dfs_59j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:carets-to-axis-vertical" {...props}></Icon>
