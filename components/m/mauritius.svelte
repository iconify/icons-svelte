<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mb9b0qbvi.css';
import '../../css/v/vv-rc2b1z.css';
import '../../css/d/desiwpbvm.css';
import '../../css/r/r130d-bgs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":24};
const content = `<path class="mb9b0qbvi"/><path class="vv-rc2b1z"/><path class="desiwpbvm"/><path class="r130d-bgs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler-flags:mauritius" {...props}></Icon>
