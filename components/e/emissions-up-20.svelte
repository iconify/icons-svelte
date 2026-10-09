<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xzjn5iovv.css';
import '../../css/m/mignyccut.css';
import '../../css/u/uq81wcb4x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="xzjn5iovv"/><path class="mignyccut"/><path class="uq81wcb4x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:emissions-up-20" {...props}></Icon>
