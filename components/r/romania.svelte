<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jwr0h7biq.css';
import '../../css/r/r_uwoyl_r.css';
import '../../css/t/t2w8mls_d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":24};
const content = `<path class="jwr0h7biq"/><path class="r_uwoyl_r"/><path class="t2w8mls_d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler-flags:romania" {...props}></Icon>
