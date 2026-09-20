<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wzfqp_bxg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="wzfqp_bxg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:badge-promotion-outline" {...props}></Icon>
