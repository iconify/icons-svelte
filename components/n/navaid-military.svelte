<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/svdy80z7e.css';
import '../../css/z/zd_-azbqb.css';
import '../../css/e/e39ud6bwf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="svdy80z7e"/><path class="zd_-azbqb"/><circle class="e39ud6bwf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:navaid-military" {...props}></Icon>
