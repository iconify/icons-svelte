<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ylqwv4a4h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ylqwv4a4h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:arrow-down-left-solid" {...props}></Icon>
