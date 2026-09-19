<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wz_fdacbr.css';
import '../../css/j/jj9znifff.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="wz_fdacbr"/><path class="jj9znifff"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:in-progress-warning" {...props}></Icon>
