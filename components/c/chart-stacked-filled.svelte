<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r3att8bhb.css';
import '../../css/s/s2tkiab1n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r3att8bhb"/><path class="s2tkiab1n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:chart-stacked-filled" {...props}></Icon>
