<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rcwxktbeb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rcwxktbeb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:rhombus-split-outline" {...props}></Icon>
