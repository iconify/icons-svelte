<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k5qb0ukzl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k5qb0ukzl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:perpendicular" {...props}></Icon>
