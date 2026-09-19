<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ubpd-wbmq.css';
import '../../css/q/qklnfea4v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="ubpd-wbmq"/><path class="qklnfea4v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="foundation:battery-full" {...props}></Icon>
