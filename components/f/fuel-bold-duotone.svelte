<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x9kk-diig.css';
import '../../css/j/j7y39ibwz.css';
import '../../css/r/r7zem_bnx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x9kk-diig"/><path class="j7y39ibwz"/><path class="r7zem_bnx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:fuel-bold-duotone" {...props}></Icon>
