<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xq4q6o5xn.css';
import '../../css/p/p72eb_bpu.css';
import '../../css/t/ty8c60bpt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="xq4q6o5xn"/><path class="p72eb_bpu"/><path class="ty8c60bpt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:jack-up-vessel-20" {...props}></Icon>
