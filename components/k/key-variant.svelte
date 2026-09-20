<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i8ppge-1h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i8ppge-1h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:key-variant" {...props}></Icon>
