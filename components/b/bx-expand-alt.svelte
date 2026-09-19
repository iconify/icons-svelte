<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p2dkfp8er.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p2dkfp8er"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bx-expand-alt" {...props}></Icon>
