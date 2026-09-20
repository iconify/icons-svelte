<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zw32n4xnb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="zw32n4xnb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:dinner" {...props}></Icon>
