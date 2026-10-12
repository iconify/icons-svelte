<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h6xyg1bap.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h6xyg1bap"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="andrsrxn:move-3d" {...props}></Icon>
