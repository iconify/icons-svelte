<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ct0xq6blj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ct0xq6blj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-skip-previous-circle" {...props}></Icon>
