<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mqwdx_ben.css';
import '../../css/y/y_fuh3bha.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="mqwdx_ben"/><path class="y_fuh3bha"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:computers-devices-electronics-memory" {...props}></Icon>
