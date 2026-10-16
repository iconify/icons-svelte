<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/svwgtwb6l.css';
import '../../css/x/xwg4fnbby.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="svwgtwb6l"/><path class="xwg4fnbby"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:iot-device-48" {...props}></Icon>
