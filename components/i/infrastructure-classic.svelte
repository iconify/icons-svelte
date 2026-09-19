<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y_wkv8bja.css';
import '../../css/p/pv_j-gb0w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="y_wkv8bja"/><path class="pv_j-gb0w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:infrastructure-classic" {...props}></Icon>
