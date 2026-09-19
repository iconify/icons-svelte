<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j-k-cebwl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j-k-cebwl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxl:claude-ai" {...props}></Icon>
