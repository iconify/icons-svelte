<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ooo659baw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ooo659baw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:chevrons-from-axis-dashed-horizontal" {...props}></Icon>
