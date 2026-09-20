<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qp2gr0pmt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="qp2gr0pmt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nonicons:json-16" {...props}></Icon>
