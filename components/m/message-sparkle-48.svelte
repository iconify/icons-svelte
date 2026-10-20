<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dyrurpboo.css';
import '../../css/v/vvmgcrxho.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="dyrurpboo"/><path class="vvmgcrxho"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:message-sparkle-48" {...props}></Icon>
