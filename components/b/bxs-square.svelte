<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c6g22izgj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c6g22izgj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-square" {...props}></Icon>
