<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fc30fdcem.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":304,"height":384};
const content = `<path class="fc30fdcem"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:fullscreen-exit" {...props}></Icon>
