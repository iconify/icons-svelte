<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cvoizu5zv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cvoizu5zv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-t-shirt" {...props}></Icon>
