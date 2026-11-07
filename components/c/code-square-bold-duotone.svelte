<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dm03gzbnp.css';
import '../../css/o/ocuj5ub7r.css';
import '../../css/i/i0clkg5td.css';
import '../../css/b/b_8fxx4ds.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dm03gzbnp"/><path class="ocuj5ub7r"/><path class="i0clkg5td"/><path class="b_8fxx4ds"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:code-square-bold-duotone" {...props}></Icon>
