<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yjdv2dp9t.css';
import '../../css/s/sla-3ib_b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="yjdv2dp9t"/><path class="sla-3ib_b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:bear-20-bold" {...props}></Icon>
