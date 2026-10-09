<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a-myk9bcg.css';
import '../../css/f/fc_ybimmu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="a-myk9bcg"/><path class="fc_ybimmu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:compliance-20" {...props}></Icon>
