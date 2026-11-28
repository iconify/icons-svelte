<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u17wqacrx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u17wqacrx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:christmas-tree-star" {...props}></Icon>
