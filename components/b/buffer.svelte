<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iou8vqn-k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iou8vqn-k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:buffer" {...props}></Icon>
