<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tdg3wxbvf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tdg3wxbvf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:chart-column-dots" {...props}></Icon>
