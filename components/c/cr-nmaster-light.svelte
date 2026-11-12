<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/poddgvb-j.css';
import '../../css/u/uqp1_ibtg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="poddgvb-j"/><path class="uqp1_ibtg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:cr-nmaster-light" {...props}></Icon>
