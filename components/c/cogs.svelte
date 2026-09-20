<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z5buxdvyt.css';
import '../../css/o/objm-ccgw.css';
import '../../css/w/w_5g2gbpt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="z5buxdvyt"/><path class="objm-ccgw"/><path class="w_5g2gbpt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:cogs" {...props}></Icon>
