<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g6cdozt2l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="g6cdozt2l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:cloudy-sun" {...props}></Icon>
