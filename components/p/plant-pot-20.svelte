<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i42u6x3xb.css';
import '../../css/s/shy242ktc.css';
import '../../css/k/ktdhr6b1o.css';
import '../../css/h/hvct_1bia.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="i42u6x3xb"/><path class="shy242ktc"/><path class="ktdhr6b1o"/><path class="hvct_1bia"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:plant-pot-20" {...props}></Icon>
