<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oeq8zv5rs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oeq8zv5rs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:chevrons-to-axis-horizontal" {...props}></Icon>
