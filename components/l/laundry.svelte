<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dq1me686k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<path class="dq1me686k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="map:laundry" {...props}></Icon>
