<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dl7697j7m.css';
import '../../css/x/x4jxcf4cm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":24};
const content = `<path class="dl7697j7m"/><path class="x4jxcf4cm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler-flags:bahrain" {...props}></Icon>
