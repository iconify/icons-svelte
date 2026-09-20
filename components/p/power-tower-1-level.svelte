<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i4yuvymwx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="i4yuvymwx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:power-tower-1-level" {...props}></Icon>
