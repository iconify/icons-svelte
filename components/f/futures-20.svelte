<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v_38zbbbr.css';
import '../../css/q/qpiu3eb1z.css';
import '../../css/v/vxcokgmud.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="v_38zbbbr"/><path class="qpiu3eb1z"/><path class="vxcokgmud"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:futures-20" {...props}></Icon>
