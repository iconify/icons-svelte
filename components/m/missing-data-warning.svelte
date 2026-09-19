<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/maczq5bmt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="maczq5bmt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:missing-data-warning" {...props}></Icon>
