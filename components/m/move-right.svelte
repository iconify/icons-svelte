<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j3z1htbsz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j3z1htbsz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:move-right" {...props}></Icon>
