<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bvnf7s1_x.css';
import '../../css/r/r2uj8dq1d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bvnf7s1_x"/><path class="r2uj8dq1d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:heart-duotone" {...props}></Icon>
