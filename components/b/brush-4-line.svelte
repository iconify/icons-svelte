<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fz3u-o5ji.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fz3u-o5ji"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:brush-4-line" {...props}></Icon>
