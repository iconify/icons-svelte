<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qbpxv2b0b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="qbpxv2b0b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:globe2" {...props}></Icon>
