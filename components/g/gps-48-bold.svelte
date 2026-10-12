<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qtgmy3b7z.css';
import '../../css/h/hodl4aclm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="qtgmy3b7z"/><path class="hodl4aclm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:gps-48-bold" {...props}></Icon>
