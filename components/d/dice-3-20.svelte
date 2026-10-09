<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qxp0_ibgn.css';
import '../../css/o/o4hofjbpc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="qxp0_ibgn"/><path class="o4hofjbpc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:dice-3-20" {...props}></Icon>
