<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ophijtbsv.css';
import '../../css/q/qg1_u7bwc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ophijtbsv"/><path class="qg1_u7bwc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:list-down-bold-duotone" {...props}></Icon>
