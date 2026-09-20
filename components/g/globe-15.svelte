<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yxrp8fbwb.css';
import '../../css/s/sp9j6lqmm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="yxrp8fbwb"/><path class="sp9j6lqmm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:globe-15" {...props}></Icon>
