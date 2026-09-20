<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xattv9ben.css';
import '../../css/i/ige1qwxfq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="xattv9ben"/><path class="ige1qwxfq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:interface-weather-snow-2-cloud-snow-snowfall-overcast-weather-precipitation-meteorology" {...props}></Icon>
