<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/khd9gq-js.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="khd9gq-js"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:computers-devices-electronics-earpod-sound" {...props}></Icon>
