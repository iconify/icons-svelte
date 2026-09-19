<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/df-lw4b_h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":512};
const content = `<path class="df-lw4b_h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:paintbrush" {...props}></Icon>
