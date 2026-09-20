<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dbhmpbcfb.css';
import '../../css/e/el-oljoyp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="dbhmpbcfb"/><path class="el-oljoyp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:aliexpress-light" {...props}></Icon>
