<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ccrevvbty.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ccrevvbty"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:binary-tree-2-filled" {...props}></Icon>
