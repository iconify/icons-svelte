<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qw3vozd0w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":432,"height":416};
const content = `<path class="qw3vozd0w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:case-download" {...props}></Icon>
