<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k8x3bri7t.css';
import '../../css/y/yf5edlbyv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k8x3bri7t"/><path class="yf5edlbyv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:charging-fill" {...props}></Icon>
