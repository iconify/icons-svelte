<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fy21efbsd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fy21efbsd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:clipboard-check-solid" {...props}></Icon>
