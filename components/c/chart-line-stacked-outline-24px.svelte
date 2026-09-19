<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/biil5ne2q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="biil5ne2q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:chart-line-stacked-outline-24px" {...props}></Icon>
