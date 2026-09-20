<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p57so_sum.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p57so_sum"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:arrow-down-right-circle" {...props}></Icon>
