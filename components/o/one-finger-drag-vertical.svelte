<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m5b2vhb1t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="m5b2vhb1t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:one-finger-drag-vertical" {...props}></Icon>
