<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iol1rclgs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="iol1rclgs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:infrared-panel-48" {...props}></Icon>
