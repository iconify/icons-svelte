<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vi4ezce8m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="vi4ezce8m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:customer" {...props}></Icon>
