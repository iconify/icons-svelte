<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bhxa0_bkq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="bhxa0_bkq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:gripper-bar-horizontal" {...props}></Icon>
