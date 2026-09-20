<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z5o6a1e-y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z5o6a1e-y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:ethernet-cable" {...props}></Icon>
