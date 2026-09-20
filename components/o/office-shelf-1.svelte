<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rjjnd6bwo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rjjnd6bwo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:office-shelf-1" {...props}></Icon>
