<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xzjn5iovv.css';
import '../../css/m/mignyccut.css';
import '../../css/b/bbd2h6sio.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="xzjn5iovv"/><path class="mignyccut"/><path class="bbd2h6sio"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:emissions-down-20" {...props}></Icon>
