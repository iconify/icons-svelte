<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lqzc6h09o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lqzc6h09o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:italic-off" {...props}></Icon>
