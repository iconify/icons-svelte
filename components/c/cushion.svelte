<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/of3dkvhwn.css';
import '../../css/v/vn6ed8z0m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="of3dkvhwn"/><path class="vn6ed8z0m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:cushion" {...props}></Icon>
