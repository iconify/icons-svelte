<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xqiziocuh.css';
import '../../css/e/e9p8wp9jq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xqiziocuh"/><path class="e9p8wp9jq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:garmin-grafana" {...props}></Icon>
