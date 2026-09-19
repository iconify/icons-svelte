<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l4tqe28pg.css';
import '../../css/d/dy_9shbsz.css';
import '../../css/y/yr6e5mbng.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l4tqe28pg"/><rect class="dy_9shbsz"/><rect class="yr6e5mbng"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:horizontal-align-left-filled" {...props}></Icon>
