<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n-3s-3ndv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="n-3s-3ndv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:right-panel-open" {...props}></Icon>
