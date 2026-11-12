<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pi7f4wb8o.css';
import '../../css/g/gbm6d6bzt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="pi7f4wb8o"/><path class="gbm6d6bzt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:mozilla-monitor-light" {...props}></Icon>
