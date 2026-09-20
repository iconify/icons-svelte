<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/igjwmybhz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":60};
const content = `<path class="igjwmybhz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:interfere-light" {...props}></Icon>
