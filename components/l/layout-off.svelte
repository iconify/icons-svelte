<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yeid-qb0q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yeid-qb0q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:layout-off" {...props}></Icon>
