<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e5_q_wbyx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="e5_q_wbyx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:md-pricetag" {...props}></Icon>
