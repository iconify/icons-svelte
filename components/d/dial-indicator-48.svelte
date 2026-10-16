<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nmtkecamq.css';
import '../../css/v/vv-azsxen.css';
import '../../css/s/sqh4xjrbe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="nmtkecamq"/><path class="vv-azsxen"/><path class="sqh4xjrbe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:dial-indicator-48" {...props}></Icon>
