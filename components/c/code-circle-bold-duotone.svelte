<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rnb90nbxf.css';
import '../../css/o/ocuj5ub7r.css';
import '../../css/i/i0clkg5td.css';
import '../../css/b/b_8fxx4ds.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rnb90nbxf"/><path class="ocuj5ub7r"/><path class="i0clkg5td"/><path class="b_8fxx4ds"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:code-circle-bold-duotone" {...props}></Icon>
