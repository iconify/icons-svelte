<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pdldgbb_g.css';
import '../../css/d/d7q3yfbdi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pdldgbb_g"/><path class="d7q3yfbdi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:call-cancel-filled" {...props}></Icon>
