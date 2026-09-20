<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qxz4xdoel.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="qxz4xdoel"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:interface-weather-moon-astronomy-moon-science-space-crescent" {...props}></Icon>
