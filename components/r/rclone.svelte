<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p_d602kex.css';
import '../../css/u/u-v0-d6uk.css';
import '../../css/q/qpp9bw75i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="p_d602kex"/><path class="u-v0-d6uk"/><path class="qpp9bw75i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:rclone" {...props}></Icon>
