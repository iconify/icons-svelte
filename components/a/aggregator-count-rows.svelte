<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uabl71b1n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="uabl71b1n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:aggregator-count-rows" {...props}></Icon>
