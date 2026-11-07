<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yfx_j7n7f.css';
import '../../css/a/avzi4zbdf.css';
import '../../css/c/c8ow5lbgf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yfx_j7n7f"/><path clip-rule="evenodd" class="avzi4zbdf"/><path class="c8ow5lbgf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:meditation-bold-duotone" {...props}></Icon>
