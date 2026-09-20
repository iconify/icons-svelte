<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u8s51ms8h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u8s51ms8h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:react" {...props}></Icon>
