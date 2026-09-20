<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ej58xi1_p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ej58xi1_p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:board-hanging-rail" {...props}></Icon>
