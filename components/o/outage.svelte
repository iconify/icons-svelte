<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ksos72b1n.css';
import '../../css/d/drkyefbiz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ksos72b1n"/><path class="drkyefbiz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:outage" {...props}></Icon>
