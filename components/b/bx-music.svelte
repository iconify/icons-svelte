<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/va0-blb8e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="va0-blb8e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bx-music" {...props}></Icon>
