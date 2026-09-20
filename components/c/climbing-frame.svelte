<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi64kac_w.css';
import '../../css/s/sup9bkb8w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="bi64kac_w"/><path class="sup9bkb8w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:climbing-frame" {...props}></Icon>
