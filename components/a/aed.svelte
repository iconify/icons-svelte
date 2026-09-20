<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l3a2qabhs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l3a2qabhs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:aed" {...props}></Icon>
