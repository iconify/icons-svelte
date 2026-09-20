<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uyzg1pb_q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uyzg1pb_q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:3-plus" {...props}></Icon>
