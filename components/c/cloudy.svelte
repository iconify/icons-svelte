<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ivz57db5z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="ivz57db5z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oi:cloudy" {...props}></Icon>
