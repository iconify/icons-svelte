<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/osl8gwbsk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="osl8gwbsk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:drag-horizontal-round" {...props}></Icon>
